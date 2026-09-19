<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq2a-_k6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="jq2a-_k6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:christiancross" /></template>
