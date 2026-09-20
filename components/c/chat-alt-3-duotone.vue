<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd6urnymg.css';
import '../../css/f/f-ksdqydc.css';
import '../../css/c/c7gfsbb7m.css';
import '../../css/s/spxynnb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bd6urnymg"/><circle class="f-ksdqydc"/><circle class="c7gfsbb7m"/><circle class="spxynnb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-3-duotone" /></template>
