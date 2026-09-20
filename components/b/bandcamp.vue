<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5xb6efyw.css';
import '../../css/h/hxjqz7bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5xb6efyw"/><path class="hxjqz7bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bandcamp" /></template>
