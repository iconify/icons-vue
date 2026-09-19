<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bztnfgb8s.css';
import '../../css/p/pwye_sbti.css';
import '../../css/h/h8fcp6xyp.css';
import '../../css/d/d86m1dbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bztnfgb8s"/><rect class="pwye_sbti"/><rect class="h8fcp6xyp"/><rect class="d86m1dbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:graph-filled" /></template>
