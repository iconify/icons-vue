<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzk36wbku.css';
import '../../css/a/a11bti4rf.css';
import '../../css/m/mhwf7crwk.css';
import '../../css/i/i155fsbdz.css';
import '../../css/f/fh7l_pbbp.css';
import '../../css/u/ufrw3bq5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzk36wbku"/><circle class="a11bti4rf"/><circle class="mhwf7crwk"/><circle class="i155fsbdz"/><circle class="fh7l_pbbp"/><circle class="ufrw3bq5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:joystick" /></template>
