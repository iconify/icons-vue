<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc25tg1zz.css';
import '../../css/b/bst9txban.css';
import '../../css/k/k8boz-k8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nc25tg1zz"/><path class="bst9txban"/><path class="k8boz-k8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:domainmod-dark" /></template>
