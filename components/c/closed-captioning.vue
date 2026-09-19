<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9thckz9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a9thckz9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:closed-captioning" /></template>
