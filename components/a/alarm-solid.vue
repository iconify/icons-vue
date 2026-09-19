<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y08kdrb1f.css';
import '../../css/w/w9izy0vjp.css';
import '../../css/m/mk4433d7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y08kdrb1f"/><path clip-rule="evenodd" class="w9izy0vjp"/><path class="mk4433d7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:alarm-solid" /></template>
