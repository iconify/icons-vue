<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="im_lx0b_v"/><path class="dk39dyrfr"/><path class="sm9fafq1b"/><path class="ym7-ii-2x"/><path class="bjvoobnqp"/><path class="g08erzblh"/><path class="ubxdfeb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-paket" /></template>
<style>
.bjvoobnqp {
  fill: var(--svg-color--add4f7, #add4f7);
  d: path("m14.248 13.118l10.541 5.246l2.145-1.056l-10.575-5.246Z");
}

.dk39dyrfr {
  fill: var(--svg-color--0a6ec9, #0a6ec9);
  d: path("M9.942 15.246L20.5 10l10.558 5.246v.693L20.5 21.185l-10.558-5.23Z");
}

.g08erzblh {
  fill: var(--svg-color--99c7f2, #99c7f2);
  d: path("m24.789 18.364l2.145-1.056v3.3l-.577-.1l-.61.742l-.957-.066Z");
}

.im_lx0b_v {
  fill: var(--svg-color--558dbf, #558dbf);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.sm9fafq1b {
  fill: var(--svg-color--0568c1, #0568c1);
  d: path("M9.942 15.246L20.5 20.492l10.558-5.246v10.508L20.467 31L9.942 25.754Z");
}

.ubxdfeb-i {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M18.322 24.682L14.759 22.9c-.2-.1-.363.017-.363.264v2.392a.76.76 0 0 0 .363.627l3.58 1.782c.2.1.363-.017.363-.264v-2.409a.78.78 0 0 0-.38-.61m-.808 1.963l-2.277-1.138a.4.4 0 0 1-.181-.33c0-.132.082-.2.181-.148l2.277 1.138a.4.4 0 0 1 .181.33c.005.131-.082.197-.181.148m.33-.825l-2.606-1.32a.4.4 0 0 1-.181-.33c0-.132.082-.2.181-.148l2.606 1.32a.4.4 0 0 1 .181.33c.001.148-.082.198-.181.148");
}

.ym7-ii-2x {
  fill: var(--svg-color--0663b4, #0663b4);
  d: path("M20.5 30.984V20.492l-10.492-5.213h-.066v10.475L20.467 31Z");
}

</style>
