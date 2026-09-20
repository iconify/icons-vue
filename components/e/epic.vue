<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwc2g5b2a.css';
import '../../css/p/pjb5o-bcb.css';
import '../../css/q/qapg4nbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwc2g5b2a"/><path class="pjb5o-bcb"/><path clip-rule="evenodd" class="qapg4nbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:epic" /></template>
