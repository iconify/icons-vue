<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqau0ibzp.css';
import '../../css/k/kpwe2lb7m.css';
import '../../css/d/djiwjacqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqau0ibzp"/><path clip-rule="evenodd" class="kpwe2lb7m"/><path class="djiwjacqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cassette-tape-filled" /></template>
