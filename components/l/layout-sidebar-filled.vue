<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grp-vub5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grp-vub5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-sidebar-filled" /></template>
