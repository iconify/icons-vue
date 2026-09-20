<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtxeimbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jtxeimbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:add-small-outline" /></template>
