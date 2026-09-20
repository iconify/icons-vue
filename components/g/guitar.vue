<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu-50lb7t.css';
import '../../css/b/brgqastdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iu-50lb7t"/><path class="brgqastdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:guitar" /></template>
