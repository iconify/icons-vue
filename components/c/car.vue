<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t63ypnw_i.css';
import '../../css/t/tw5hhubaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t63ypnw_i"/><path class="tw5hhubaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:car" /></template>
