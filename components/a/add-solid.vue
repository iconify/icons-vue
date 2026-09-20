<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-kfp_d1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="a-kfp_d1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:add-solid" /></template>
