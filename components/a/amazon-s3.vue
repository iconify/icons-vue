<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nstvbxb0m.css';
import '../../css/z/zukjp5bxm.css';
import '../../css/e/edbkswbvk.css';
import '../../css/e/ei60xkbzq.css';
import '../../css/t/ts74kj5dn.css';
import '../../css/u/ua6tm9bna.css';
import '../../css/m/m9ad-ebcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nstvbxb0m"/><path class="zukjp5bxm"/><path class="edbkswbvk"/><path class="ei60xkbzq"/><path class="ts74kj5dn"/><path class="ua6tm9bna"/><path class="m9ad-ebcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-s3" /></template>
