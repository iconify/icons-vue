<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj7dvbcbq.css';
import '../../css/t/tnw5n4brt.css';
import '../../css/d/deaxs3sre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj7dvbcbq wm-k"/><path class="tnw5n4brt wm-a"/><path class="deaxs3sre wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:log-out" /></template>
