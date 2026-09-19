<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebxc1ccgv.css';
import '../../css/g/gwken0w2c.css';
import '../../css/s/sy_a5lx3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebxc1ccgv"/><path clip-rule="evenodd" class="gwken0w2c"/><path clip-rule="evenodd" class="sy_a5lx3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:lifebuoy-outline" /></template>
