<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl5uzhbhz.css';
import '../../css/a/a2koo-blx.css';
import '../../css/t/twwa4bckn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz wm-k"/><path class="a2koo-blx wm-a"/><path class="twwa4bckn wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle-chevron-right" /></template>
