<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g83jubcwx.css';
import '../../css/p/plpx6bh0t.css';
import '../../css/b/bs59tnbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g83jubcwx"/><path class="plpx6bh0t"/><path clip-rule="evenodd" class="bs59tnbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-old-outline" /></template>
