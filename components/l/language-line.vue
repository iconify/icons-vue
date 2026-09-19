<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f54kc8x7l.css';
import '../../css/z/zyn_ifbxm.css';
import '../../css/h/hhybubb0v.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 f54kc8x7l"/><path class="clr-i-outline clr-i-outline-path-2 zyn_ifbxm"/><path class="clr-i-outline clr-i-outline-path-3 hhybubb0v"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:language-line" /></template>
