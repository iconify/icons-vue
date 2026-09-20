<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okpx9ccms.css';
import '../../css/a/a59ct2b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okpx9ccms"/><path class="a59ct2b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:download-bottom-bold" /></template>
