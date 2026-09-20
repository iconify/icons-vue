<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjuxlcckf.css';
import '../../css/e/ejuf35bcd.css';
import '../../css/x/xwkcvac5a.css';
import '../../css/w/whf4zhv6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjuxlcckf"/><path class="ejuf35bcd"/><path clip-rule="evenodd" class="xwkcvac5a"/><path class="whf4zhv6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lighthouse-fill" /></template>
