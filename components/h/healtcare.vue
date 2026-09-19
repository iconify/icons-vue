<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mmdspp3nh.css';
import '../../css/b/bybxiz3os.css';
import '../../css/z/z2p-kumju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mmdspp3nh"/><path class="bybxiz3os"/><path class="z2p-kumju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:healtcare" /></template>
