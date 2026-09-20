<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv628ykgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv628ykgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:equal" /></template>
