<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mlhp95bav"/><path class="q11p3h5-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hob-child-lock" /></template>
<style>
.mlhp95bav {
  d: path("M12.2 17.5H2.5v-15h15v9.7");
}

.q11p3h5-r {
  d: path("M5 6.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm6.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM5 13.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm9.981.256q.019-.127.019-.256q0-.086-.008-.172t-.026-.169q-.016-.085-.041-.167t-.058-.162q-.033-.079-.074-.155t-.088-.147q-.048-.072-.102-.138q-.055-.067-.116-.127q-.06-.061-.127-.116q-.066-.054-.138-.102q-.071-.048-.147-.088q-.076-.041-.155-.074q-.08-.033-.162-.058t-.167-.041t-.169-.026t-.172-.008q-.086 0-.172.008t-.169.026q-.085.016-.167.041t-.162.058q-.079.033-.155.074t-.147.088q-.072.048-.138.102q-.067.055-.127.116q-.061.06-.116.127q-.054.066-.102.138q-.048.071-.088.147q-.041.076-.074.155q-.033.08-.058.162t-.041.167t-.026.169t-.008.172q0 .112.014.224t.043.22t.071.213t.098.203q.055.098.122.188q.068.09.146.17t.166.151t.184.129M15 17.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
