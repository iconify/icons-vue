<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/a/algf38bxk.css';
import '../../css/b/b-jujfljh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGRIzbSbuD" x1="18.6" x2="534.7" y1="-27.8" y2="488.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGRIzbSbuD)" class="algf38bxk"/><path class="b-jujfljh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adguard-home-central-manager-light" /></template>
