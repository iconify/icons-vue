<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7aemk5fe.css';
import '../../css/x/x41xvfi0c.css';
import '../../css/y/y97ssxb3n.css';
import '../../css/m/m2h8cktnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7aemk5fe"/><path class="x41xvfi0c"/><path class="y97ssxb3n"/><path clip-rule="evenodd" class="m2h8cktnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-password-unlocked-outline" /></template>
