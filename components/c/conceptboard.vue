<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejshfpu0b.css';
import '../../css/p/pm7rgls4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":260,"height":260};
const content = `<path class="ejshfpu0b"/><path class="pm7rgls4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:conceptboard" /></template>
