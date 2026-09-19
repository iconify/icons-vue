<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb02gcc3k.css';
import '../../css/b/b9ttszcks.css';
import '../../css/k/kh4p7s4vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb02gcc3k"/><path class="b9ttszcks"/><path class="kh4p7s4vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-jquery" /></template>
