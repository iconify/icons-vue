<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clmjnb28i.css';
import '../../css/s/sayrawf8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="clmjnb28i"/><path class="sayrawf8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flow-like-light" /></template>
