<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scx1z0ypn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scx1z0ypn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:badge-verified-solid" /></template>
