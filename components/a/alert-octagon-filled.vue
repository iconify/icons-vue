<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuvf9wvfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuvf9wvfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-octagon-filled" /></template>
