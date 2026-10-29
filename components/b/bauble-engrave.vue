<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/czyptrb8u.css';
import '../../css/v/v_p800b7x.css';
import '../../css/z/z8wsx4v4t.css';
import '../../css/x/x4e1woonj.css';
import '../../css/i/ip7h18bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="czyptrb8u wm-k"/><path class="v_p800b7x wm-a"/><path class="wm-shadow z8wsx4v4t"/><path class="wm-k x4e1woonj"/><path class="ip7h18bdm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bauble-engrave" /></template>
