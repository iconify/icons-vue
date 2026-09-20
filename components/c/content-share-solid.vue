<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqd3vf-lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqd3vf-lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:content-share-solid" /></template>
