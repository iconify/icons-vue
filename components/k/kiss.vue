<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beayis30x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="beayis30x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:kiss" /></template>
