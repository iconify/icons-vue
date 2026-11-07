<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfjrhsbdn.css';
import '../../css/t/tvzowjb2p.css';
import '../../css/m/mym-u-jww.css';
import '../../css/b/bogwy2v0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfjrhsbdn"/><path clip-rule="evenodd" class="tvzowjb2p"/><path clip-rule="evenodd" class="mym-u-jww"/><path clip-rule="evenodd" class="bogwy2v0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-outline" /></template>
