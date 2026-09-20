<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r81h0lbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r81h0lbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:actigraph" /></template>
