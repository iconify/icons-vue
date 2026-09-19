<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df7_jw1qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="df7_jw1qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:field-of-view" /></template>
