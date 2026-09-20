<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqfj2p6jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqfj2p6jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-cancel" /></template>
