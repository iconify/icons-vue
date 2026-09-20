<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yipiq0bie.css';
import '../../css/a/ag0fqubbm.css';
import '../../css/b/b10cdoboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yipiq0bie"/><path class="ag0fqubbm"/><path clip-rule="evenodd" class="b10cdoboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aura" /></template>
