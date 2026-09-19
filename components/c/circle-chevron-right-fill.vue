<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6cmpy5to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t6cmpy5to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevron-right-fill" /></template>
