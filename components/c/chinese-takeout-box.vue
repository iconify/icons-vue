<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmmo3bbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chinese-takeout-box" /></template>
<style>
.pmmo3bbfy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 4.75h-.338Q15.639 2.688 12 2.688T7.838 4.75H7.5q-.09 0-.177.021t-.166.062t-.148.1q-.067.058-.119.131l-2.5 3.5q-.087.121-.121.267q-.033.145-.009.292q.025.147.104.274t.2.213q.105.075.228.111q-.312.668-.175 1.458l1.392 8q.361 2.071 2.463 2.071h7.056q2.102 0 2.463-2.071l1.392-8q.137-.79-.175-1.458q.123-.036.228-.111q.06-.043.111-.096q.05-.054.089-.117t.066-.132q.026-.069.038-.142t.01-.146q-.003-.074-.019-.146q-.017-.072-.047-.139q-.031-.068-.074-.128l-2.5-3.5q-.052-.073-.119-.131q-.068-.059-.148-.1t-.166-.062t-.177-.021M12 4.188q-1.8 0-2.422.562h4.844Q13.8 4.188 12 4.188m-.75 2.062v2H7.081q-.363 0-.685.086l1.49-2.086zm1.5 2v-2h3.364l1.49 2.086q-.322-.086-.685-.086z");
}

</style>
