<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enpcx5b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="enpcx5b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:creditcard" /></template>
