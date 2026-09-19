<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6f34bfwl.css';
import '../../css/n/nud8t5e2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6f34bfwl"/><path clip-rule="evenodd" class="nud8t5e2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lock-outline" /></template>
