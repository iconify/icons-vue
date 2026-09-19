<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebflwhkmy.css';
import '../../css/o/o98-wvvyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ebflwhkmy"/><path class="o98-wvvyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bug-sharp" /></template>
