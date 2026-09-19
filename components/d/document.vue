<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu4jbsbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="mu4jbsbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:document" /></template>
