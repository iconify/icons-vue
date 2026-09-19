<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkgu3wbhs.css';
import '../../css/d/ds9yhnr-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkgu3wbhs"/><path class="ds9yhnr-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chat-alt" /></template>
