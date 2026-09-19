<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpbvj0b9n.css';
import '../../css/n/neukm1fuz.css';
import '../../css/k/kr2jicboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="xpbvj0b9n"/><rect class="neukm1fuz"/><rect class="kr2jicboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-column-right-filled" /></template>
