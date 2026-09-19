<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka6cs0bzz.css';
import '../../css/r/rek-56b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka6cs0bzz"/><path class="rek-56b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-stand-filled" /></template>
