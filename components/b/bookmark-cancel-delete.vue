<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q--benb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q--benb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bookmark-cancel-delete" /></template>
