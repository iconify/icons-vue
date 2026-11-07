<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2nrf10bf.css';
import '../../css/w/waj24z7nm.css';
import '../../css/q/qv7m4ujqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path clip-rule="evenodd" class="waj24z7nm"/><path clip-rule="evenodd" class="qv7m4ujqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-zip-bold-duotone" /></template>
