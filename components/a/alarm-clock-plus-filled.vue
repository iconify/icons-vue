<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koso66sca.css';
import '../../css/d/du-r1xbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="koso66sca"/><path class="du-r1xbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:alarm-clock-plus-filled" /></template>
