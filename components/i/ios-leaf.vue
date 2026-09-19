<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/becfagpcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="becfagpcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-leaf" /></template>
