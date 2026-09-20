<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9-u3mh1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y9-u3mh1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arizona-with-capital-star" /></template>
