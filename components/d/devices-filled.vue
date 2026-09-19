<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as-6o-bsz.css';
import '../../css/x/x48sfiyvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="as-6o-bsz"/><path class="x48sfiyvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:devices-filled" /></template>
