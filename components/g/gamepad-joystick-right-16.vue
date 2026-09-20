<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk09y49yr.css';
import '../../css/y/yvlpmubcp.css';
import '../../css/b/bw4bmeb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kk09y49yr"/><path clip-rule="evenodd" class="yvlpmubcp"/><path class="bw4bmeb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-joystick-right-16" /></template>
