<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pozm4jbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pozm4jbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cms" /></template>
