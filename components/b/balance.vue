<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7g30otht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n7g30otht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:balance" /></template>
