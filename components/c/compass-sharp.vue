<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn3rdabgq.css';
import '../../css/n/nmv6y45kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn3rdabgq"/><path class="nmv6y45kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:compass-sharp" /></template>
