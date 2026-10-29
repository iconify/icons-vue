<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ywfyxmo.css';
import '../../css/e/ebjwpkoxt.css';
import '../../css/v/v2i4q_bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ywfyxmo wm-k"/><path class="ebjwpkoxt wm-a"/><path class="v2i4q_bal wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chef-hat" /></template>
