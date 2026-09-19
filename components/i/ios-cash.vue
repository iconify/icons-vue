<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_1hnfwlj.css';
import '../../css/m/m50re4ijw.css';
import '../../css/o/okx3-dbox.css';
import '../../css/a/axr2tcbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_1hnfwlj"/><path class="m50re4ijw"/><path class="okx3-dbox"/><circle class="axr2tcbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cash" /></template>
