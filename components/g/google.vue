<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh7jpabfb.css';
import '../../css/g/gak2xbgdu.css';
import '../../css/h/hs9m8_bbv.css';
import '../../css/b/bqa1tob7t.css';
import '../../css/m/mt44fjb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xh7jpabfb"/><path class="gak2xbgdu"/><path class="hs9m8_bbv"/><path class="bqa1tob7t"/><path class="mt44fjb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:google" /></template>
