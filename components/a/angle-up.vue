<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bofd2xzrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bofd2xzrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-up" /></template>
