<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j05mr2p2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j05mr2p2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:floppy-disk-solid" /></template>
