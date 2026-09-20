<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxqhxbc1l.css';
import '../../css/f/fo7gk3lhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gxqhxbc1l"/><path class="fo7gk3lhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-dentistry-tooth" /></template>
