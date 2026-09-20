<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvlhzvb1u.css';
import '../../css/n/ngozc736n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hvlhzvb1u"/><path clip-rule="evenodd" class="ngozc736n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-minus-solid" /></template>
