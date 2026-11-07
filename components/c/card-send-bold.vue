<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuhjhbb0m.css';
import '../../css/z/z_zrozxsx.css';
import '../../css/u/uar6m87sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uuhjhbb0m"/><path class="z_zrozxsx"/><path clip-rule="evenodd" class="uar6m87sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-send-bold" /></template>
