<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_dkpgfkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p_dkpgfkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layout-side-content-right" /></template>
