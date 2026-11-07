<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt1a48lct.css';
import '../../css/z/z019-jv4q.css';
import '../../css/u/uam-iwbek.css';
import '../../css/w/wqfg_ypqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt1a48lct"/><path class="z019-jv4q"/><path class="uam-iwbek"/><path class="wqfg_ypqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-2-bold-duotone" /></template>
