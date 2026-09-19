<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3utn-y9c.css';
import '../../css/w/waww24_9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3utn-y9c"/><path class="waww24_9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bug-alt" /></template>
