<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7ilcxb3j.css';
import '../../css/p/prq9nybvi.css';
import '../../css/e/exlutqbvg.css';
import '../../css/s/s64hpnbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7ilcxb3j"/><path class="prq9nybvi"/><path class="exlutqbvg"/><path clip-rule="evenodd" class="s64hpnbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-password-outline" /></template>
