<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxao0zblb.css';
import '../../css/m/mdvlj20nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxao0zblb"/><path clip-rule="evenodd" class="mdvlj20nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:eye-solid" /></template>
