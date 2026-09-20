<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vutzp7v9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vutzp7v9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feedpushr-dark" /></template>
