<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lipfkbc6w"/><path class="sou2foirk"/><path class="vucs9xb2e"/><path class="f-vugpb1m"/><path class="puree9gfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-caribbean-netherlands" /></template>
<style>
.f-vugpb1m {
  d: path("m16.513 15.894l1.192-.688l-1.192-.688a5.566 5.566 0 0 0-4.825-4.825L11 8.5l-.688 1.192a5.566 5.566 0 0 0-4.825 4.825l-1.192.688l1.192.688a5.566 5.566 0 0 0 4.825 4.825L11 21.912l.688-1.192a5.57 5.57 0 0 0 4.825-4.826M11 20.048a4.85 4.85 0 0 1-4.843-4.842c0-2.67 2.172-4.842 4.843-4.842s4.842 2.172 4.842 4.842A4.847 4.847 0 0 1 11 20.048");
}

.lipfkbc6w {
  fill: var(--svg-color--eeeded, #eeeded);
  d: path("M1.369 30.011L34.633 5.99A4 4 0 0 0 32 5H13.25L0 15.833V27a3.98 3.98 0 0 0 1.369 3.011");
}

.puree9gfh {
  fill: var(--svg-color--dc171d, #dc171d);
  d: path("m12.914 15.206l.957-1.658h-1.914L11 11.891l-.957 1.657H8.129l.957 1.658l-.957 1.657h1.914L11 18.521l.957-1.658h1.914z");
}

.sou2foirk {
  fill: var(--svg-color--012a87, #012a87);
  d: path("M34.633 5.99L1.369 30.011A4 4 0 0 0 4 31h28a4 4 0 0 0 4-4V9a4 4 0 0 0-1.367-3.01");
}

.vucs9xb2e {
  fill: var(--svg-color--f9d90f, #f9d90f);
  d: path("M4 5a4 4 0 0 0-4 4v6.833L13.25 5z");
}

</style>
