<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdowcxbbg.css';
import '../../css/l/lalksfbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdowcxbbg"/><path class="lalksfbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-information-circle-outline" /></template>
