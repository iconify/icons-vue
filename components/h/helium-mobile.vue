<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-nq5eyhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-nq5eyhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:helium-mobile" /></template>
