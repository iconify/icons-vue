<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb5fwjseb.css';
import '../../css/x/xpcye44-n.css';
import '../../css/k/kcxdw0blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb5fwjseb"/><path class="xpcye44-n"/><path clip-rule="evenodd" class="kcxdw0blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:domi" /></template>
