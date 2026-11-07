<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8_v07a_t.css';
import '../../css/l/lnl964nao.css';
import '../../css/z/z4zklhbom.css';
import '../../css/y/yzrr_8gta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8_v07a_t"/><path class="lnl964nao"/><path clip-rule="evenodd" class="z4zklhbom"/><path class="yzrr_8gta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-play-bold" /></template>
