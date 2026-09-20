<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9ot2f44q.css';
import '../../css/i/it9p5abzo.css';
import '../../css/n/n0frhibvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ot2f44q"/><path class="it9p5abzo"/><path class="n0frhibvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:google-drive-alt" /></template>
