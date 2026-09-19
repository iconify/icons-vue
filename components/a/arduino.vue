<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9xb2qb7w.css';
import '../../css/g/gdngdpbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y9xb2qb7w"/><path class="gdngdpbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:arduino" /></template>
