<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leiavflem.css';
import '../../css/a/aumpujaom.css';
import '../../css/y/yv4_o-byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="leiavflem"/><path class="aumpujaom"/><path class="yv4_o-byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-minimalistic-bold-duotone" /></template>
