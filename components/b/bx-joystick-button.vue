<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbvbi9oey.css';
import '../../css/l/lp7eaq79j.css';
import '../../css/n/n1xy6nh9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbvbi9oey"/><path class="lp7eaq79j"/><circle class="n1xy6nh9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-joystick-button" /></template>
