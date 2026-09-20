<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-641g.css';
import '../../css/s/so-from-10.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-641g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-small-down" /></template>
