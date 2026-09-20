<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zibiadcci.css';
import '../../css/a/aq7z88bzf.css';
import '../../css/q/qtsxnt9xi.css';
import '../../css/b/btlc75bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zibiadcci"/><path class="aq7z88bzf"/><path clip-rule="evenodd" class="qtsxnt9xi"/><path clip-rule="evenodd" class="btlc75bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:emoji-laugh-duotone" /></template>
