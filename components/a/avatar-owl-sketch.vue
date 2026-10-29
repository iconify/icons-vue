<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/go7m5qb9b.css';
import '../../css/j/jfnbg6t3e.css';
import '../../css/b/b5iz41bba.css';
import '../../css/g/gkbm3cc5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="go7m5qb9b"/><path class="jfnbg6t3e wm-k"/><path class="b5iz41bba wm-k"/><path class="gkbm3cc5v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-owl-sketch" /></template>
