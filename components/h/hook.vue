<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpgxckbdv.css';
import '../../css/u/us1tjmb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpgxckbdv"/><path class="us1tjmb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hook" /></template>
