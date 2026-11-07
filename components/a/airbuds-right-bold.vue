<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iarzmjb8m.css';
import '../../css/g/ge7vrqbtr.css';
import '../../css/l/lxq4dhkod.css';
import '../../css/s/s2-2a1b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iarzmjb8m"/><path clip-rule="evenodd" class="ge7vrqbtr"/><path class="lxq4dhkod"/><path clip-rule="evenodd" class="s2-2a1b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-right-bold" /></template>
