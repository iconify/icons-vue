<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9infz.css';
import '../../css/i/iw1iew.css';
import '../../css/y/y4wbml.css';
import '../../css/b/bdp70y.css';
import '../../css/r/rmfyct.css';
import '../../css/s/so-from-4.css';
import '../../css/t/tr-6vhkny.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';
import '../../css/t/tr--mk6os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9infz iw1iew y4wbml"/><path class="bdp70y iw1iew"/><path class="iw1iew rmfyct y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:bell-filled-loop" /></template>
