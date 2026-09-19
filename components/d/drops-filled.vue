<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjjreccxy.css';
import '../../css/t/t_s_xqb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjjreccxy"/><path class="t_s_xqb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:drops-filled" /></template>
