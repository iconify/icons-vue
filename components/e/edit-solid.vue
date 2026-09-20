<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnh7j8q2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gnh7j8q2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:edit-solid" /></template>
