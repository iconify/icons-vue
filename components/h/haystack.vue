<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pht4l3yoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pht4l3yoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:haystack" /></template>
