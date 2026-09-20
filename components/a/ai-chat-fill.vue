<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnacsvbpp.css';
import '../../css/t/t-rbbb6gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnacsvbpp"/><path clip-rule="evenodd" class="t-rbbb6gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-chat-fill" /></template>
