<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryrhgi3ds.css';
import '../../css/x/x43m2tg3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryrhgi3ds"/><path class="x43m2tg3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-cog-filled" /></template>
