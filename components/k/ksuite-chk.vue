<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx3v_ob6p.css';
import '../../css/k/ku8imqgff.css';
import '../../css/u/uxn5tubya.css';
import '../../css/y/yjwzayklo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fx3v_ob6p"/><path class="ku8imqgff"/><path class="uxn5tubya"/><path class="yjwzayklo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-chk" /></template>
