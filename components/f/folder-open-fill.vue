<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnh_m9b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pnh_m9b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-open-fill" /></template>
