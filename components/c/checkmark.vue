<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku7951bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku7951bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:checkmark" /></template>
