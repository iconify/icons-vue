<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz2cj4b0b.css';
import '../../css/m/md07ymbpc.css';
import '../../css/k/kc89csb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pz2cj4b0b"/><path clip-rule="evenodd" class="md07ymbpc"/><path class="kc89csb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:koin" /></template>
