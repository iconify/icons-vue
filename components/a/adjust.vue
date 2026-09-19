<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpp8mr3id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="vpp8mr3id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:adjust" /></template>
