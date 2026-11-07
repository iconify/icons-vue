<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pklythb1b.css';
import '../../css/x/x2jcmsnbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pklythb1b"/><path clip-rule="evenodd" class="x2jcmsnbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kick-scooter-bold-duotone" /></template>
