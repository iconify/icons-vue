<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgsgyebyg.css';
import '../../css/m/mq7oxpbxg.css';
import '../../css/a/ariofzdtp.css';
import '../../css/o/ooetbbcxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgsgyebyg wm-k"/><path class="mq7oxpbxg wm-a"/><path class="ariofzdtp wm-a"/><path class="ooetbbcxz wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cast" /></template>
