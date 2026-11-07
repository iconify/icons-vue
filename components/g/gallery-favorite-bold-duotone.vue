<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhvzr3pxx.css';
import '../../css/v/vwvsfxegk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhvzr3pxx"/><path clip-rule="evenodd" class="vwvsfxegk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-favorite-bold-duotone" /></template>
