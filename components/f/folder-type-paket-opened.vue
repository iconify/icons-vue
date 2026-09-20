<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wmy0s9hki"/><path class="q1imd7ygz"/><path class="vu8p_ebar"/><path class="sa3hk62ye"/><path class="c0wm7seht"/><path class="c0i1coh-o"/><path class="ca6hwfblz"/><path class="h94-ethed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-paket-opened" /></template>
<style>
.c0i1coh-o {
  fill: var(--svg-color--add4f7, #add4f7);
  d: path("m14.148 13.118l10.541 5.246l2.145-1.056l-10.575-5.246Z");
}

.c0wm7seht {
  fill: var(--svg-color--0663b4, #0663b4);
  d: path("M20.4 30.984V20.492L9.908 15.279h-.066v10.475L20.367 31Z");
}

.ca6hwfblz {
  fill: var(--svg-color--99c7f2, #99c7f2);
  d: path("m24.689 18.364l2.145-1.056v3.3l-.577-.1l-.61.742l-.957-.066Z");
}

.h94-ethed {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M18.222 24.682L14.659 22.9c-.2-.1-.363.017-.363.264v2.392a.76.76 0 0 0 .363.627l3.58 1.782c.2.1.363-.017.363-.264v-2.409a.78.78 0 0 0-.38-.61m-.808 1.963l-2.277-1.138a.4.4 0 0 1-.181-.33c0-.132.082-.2.181-.148l2.277 1.138a.4.4 0 0 1 .181.33c.005.131-.082.197-.181.148m.33-.825l-2.606-1.32a.4.4 0 0 1-.181-.33c0-.132.082-.2.181-.148l2.606 1.32a.4.4 0 0 1 .181.33c.001.148-.082.198-.181.148");
}

.q1imd7ygz {
  fill: var(--svg-color--7baddb, #7baddb);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.sa3hk62ye {
  fill: var(--svg-color--0568c1, #0568c1);
  d: path("M9.842 15.246L20.4 20.492l10.558-5.246v10.508L20.367 31L9.842 25.754Z");
}

.vu8p_ebar {
  fill: var(--svg-color--0a6ec9, #0a6ec9);
  d: path("M9.842 15.246L20.4 10l10.558 5.246v.693L20.4 21.185l-10.558-5.23Z");
}

.wmy0s9hki {
  fill: var(--svg-color--7baddb, #7baddb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

</style>
