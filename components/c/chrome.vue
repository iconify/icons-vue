<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9nj1-bpg.css';
import '../../css/z/znrlbq9xw.css';
import '../../css/p/padkusb7b.css';
import '../../css/t/tlr6z7bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9nj1-bpg"/><path class="znrlbq9xw"/><path class="padkusb7b"/><path class="tlr6z7bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chrome" /></template>
