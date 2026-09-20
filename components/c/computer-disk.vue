<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y-k8z6bvj"/><path class="s9loqbbut"/><path class="xxi_4jb6i"/><linearGradient id="SVGWYk0X6qU" x1="34.657" x2="31.029" y1="44.491" y2="50.352" gradientUnits="userSpaceOnUse"><stop offset="0" class="glc1z5wma"/><stop offset=".95" class="omwu0h0ye"/></linearGradient><path fill="url(#SVGWYk0X6qU)" class="ieuk_5hlo"/><linearGradient id="SVGtLMrHd6s" x1="38.141" x2="48.932" y1="40.904" y2="31.695" gradientUnits="userSpaceOnUse"><stop offset="0" class="glc1z5wma"/><stop offset=".989" class="ag9il_ber"/><stop offset="1" class="omwu0h0ye"/></linearGradient><path fill="url(#SVGtLMrHd6s)" class="qq4gjn1xo"/><linearGradient id="SVGPDHz9bNc" x1="34.103" x2="33.579" y1="48.856" y2="56.277" gradientTransform="rotate(6.603 -13.46 14.438)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i9kavkbea"/><stop offset=".93" class="jijfinbno"/></linearGradient><path fill="url(#SVGPDHz9bNc)" class="z1t-t9bjk"/><linearGradient id="SVGLPlOis0T" x1="34.478" x2="41.061" y1="45.128" y2="32.508" gradientTransform="rotate(6.603 -13.46 14.438)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i9kavkbea"/><stop offset=".93" class="jijfinbno"/></linearGradient><path fill="url(#SVGLPlOis0T)" class="ubcaonr9g"/><linearGradient id="SVGbDa2CecK" x1="45.492" x2="39.352" y1="33.598" y2="38.202" gradientUnits="userSpaceOnUse"><stop offset="0" class="s5lrcw9lk"/><stop offset=".926" class="coly_02ng"/></linearGradient><path fill="url(#SVGbDa2CecK)" class="dlvxigryq"/><linearGradient id="SVGPrM4dbzm" x1="53.405" x2="63.451" y1="31.356" y2="28.659" gradientUnits="userSpaceOnUse"><stop offset="0" class="s5lrcw9lk"/><stop offset=".947" class="coly_02ng"/></linearGradient><path fill="url(#SVGPrM4dbzm)" class="jmo67ubro"/><linearGradient id="SVGklqXldej" x1="95" x2="98.806" y1="48.291" y2="57.514" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset=".628" class="stui2mbih"/></linearGradient><path fill="url(#SVGklqXldej)" class="jg-wvsi5c"/><linearGradient id="SVGZTJrKc8h" x1="93.391" x2="91.112" y1="45.481" y2="41.481" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset=".907" class="stui2mbih"/></linearGradient><path fill="url(#SVGZTJrKc8h)" class="jnxyipxxa"/><linearGradient id="SVGCbu8pemV" x1="36.143" x2="37.352" y1="84.388" y2="86.341" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset=".907" class="stui2mbih"/></linearGradient><path fill="url(#SVGCbu8pemV)" class="mk30hxbkt"/><linearGradient id="SVG1YrVzezz" x1="32.583" x2="28.862" y1="80.69" y2="69.621" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset=".907" class="stui2mbih"/></linearGradient><path fill="url(#SVG1YrVzezz)" class="kyr-omblw"/><linearGradient id="SVGubtKMSFF" x1="-19.454" x2="-23.082" y1="-6.239" y2="-.379" gradientTransform="rotate(179.043 36.66 38.838)" gradientUnits="userSpaceOnUse"><stop offset="0" class="glc1z5wma"/><stop offset=".95" class="omwu0h0ye"/></linearGradient><path fill="url(#SVGubtKMSFF)" class="xjoe-_b7o"/><linearGradient id="SVGrxwVQcIM" x1="-15.918" x2="-5.128" y1="-9.905" y2="-19.114" gradientTransform="rotate(179.043 36.66 38.838)" gradientUnits="userSpaceOnUse"><stop offset="0" class="glc1z5wma"/><stop offset=".989" class="ag9il_ber"/><stop offset="1" class="omwu0h0ye"/></linearGradient><path fill="url(#SVGrxwVQcIM)" class="pvwmlqbjg"/><linearGradient id="SVGmYwNjcKS" x1="-25.559" x2="-26.082" y1="4.782" y2="12.204" gradientTransform="rotate(185.647 38.042 35.937)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i9kavkbea"/><stop offset=".93" class="jijfinbno"/></linearGradient><path fill="url(#SVGmYwNjcKS)" class="i4k5w5b9z"/><linearGradient id="SVGithjNe7J" x1="-25.177" x2="-18.594" y1=".903" y2="-11.716" gradientTransform="rotate(185.647 38.042 35.937)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i9kavkbea"/><stop offset=".93" class="jijfinbno"/></linearGradient><path fill="url(#SVGithjNe7J)" class="sau8_ccyd"/><linearGradient id="SVGfGH6DbbV" x1="-8.453" x2="-14.592" y1="-17.091" y2="-12.486" gradientTransform="rotate(179.043 36.66 38.838)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s5lrcw9lk"/><stop offset=".926" class="coly_02ng"/></linearGradient><path fill="url(#SVGfGH6DbbV)" class="kwmegfb7a"/><linearGradient id="SVG7uq1xcrU" x1="-.5" x2="9.546" y1="-19.385" y2="-22.083" gradientTransform="rotate(179.043 36.66 38.838)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s5lrcw9lk"/><stop offset=".947" class="coly_02ng"/></linearGradient><path fill="url(#SVG7uq1xcrU)" class="cdiyr54bk"/><path class="xwa60cb6r"/><path class="dtmarnbvi"/><path class="bwd-c1b4c"/><path class="dyaktp03q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:computer-disk" /></template>
<style>
.ag9il_ber {
  stop-color: var(--svg-color--fff9c4, #fff9c4);
  stop-opacity: 0.007;
}

.bwd-c1b4c {
  fill: var(--svg-color--212121, #212121);
  d: path("M84.01 77.26c-.8 0-1.5-.7-1.5-1.5V53.5c0-.8.7-1.5 1.5-1.5l39.89.84l.1 24.42z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cdiyr54bk {
  d: path("m58.75 77.57l9.51 43.04s5.7-.42 11.53-2.16c6.13-1.82 11.72-4.95 11.72-4.95L69.37 77.21s-2.46 1.13-5.36 1.2s-5.26-.84-5.26-.84");
}

.coly_02ng {
  stop-color: var(--svg-color--80deea, #80deea);
  stop-opacity: 0;
}

.d-llkv2cb {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.5;
}

.dlvxigryq {
  d: path("M28.4 19.46c-3.89 3.05-6.94 6.57-6.94 6.57L52.8 55.09s1.12-1.3 2.6-2.45s3.05-1.77 3.05-1.77L36.92 13.84s-4.64 2.57-8.52 5.62");
}

.dtmarnbvi {
  fill: var(--svg-color--82aec0, #82aec0);
  d: path("M64 9.86c29.83 0 54.14 24.32 54.14 54.14S93.83 118.14 64 118.14S9.86 93.83 9.86 64S34.17 9.86 64 9.86m0 71.24c9.4 0 17.1-7.69 17.1-17.1S73.4 46.9 64 46.9S46.9 54.6 46.9 64S54.6 81.1 64 81.1m0-74.09C32.56 7.01 7.01 32.56 7.01 64S32.56 120.99 64 120.99S120.99 95.44 120.99 64S95.44 7.01 64 7.01m0 71.24c-7.88 0-14.25-6.36-14.25-14.25S56.12 49.75 64 49.75S78.25 56.12 78.25 64c.09 7.88-6.27 14.25-14.25 14.25");
}

.dyaktp03q {
  fill: var(--svg-color--eee, #eee);
  d: path("M85.2 75.9c-.8 0-1.5-.7-1.5-1.5V53.5c0-.8.7-1.5 1.5-1.5H124v23.9z");
}

.glc1z5wma {
  stop-color: var(--svg-color--fff9c4, #fff9c4);
  stop-opacity: 0.6;
}

.i4k5w5b9z {
  d: path("m120.35 69.15l-41.88-6.44s.05 1.23-.03 2.69s-.42 2.43-.42 2.43l39.81 13.51s.88-2.3 1.61-5.86c.74-3.56.91-6.33.91-6.33");
}

.i9kavkbea {
  stop-color: var(--svg-color--ffc2c8, #ffc2c8);
  stop-opacity: 0.8;
}

.ieuk_5hlo {
  d: path("m10.77 43.61l39.28 17.38s.37-1.46 1.05-3.05s1.77-2.87 1.77-2.87L17.9 30.45s-1.97 2.69-4.04 6.43c-2.06 3.75-3.09 6.73-3.09 6.73");
}

.jg-wvsi5c {
  d: path("M114.72 38.01L75.94 55.93c3.67 5.3 2.34 10.38 2.34 10.38l42.58-6.2c-.48-9.19-3.76-17.46-6.14-22.1");
}

.jijfinbno {
  stop-color: var(--svg-color--ffcdd2, #ffcdd2);
  stop-opacity: 0;
}

.jmo67ubro {
  d: path("M69.07 50.68L60.28 7.13s-5.7.33-11.57 1.96c-6.16 1.72-11.8 4.75-11.8 4.75l21.53 37.01s2.48-1.09 5.38-1.11s5.25.94 5.25.94");
}

.jnxyipxxa {
  d: path("M103.42 22.86L71.37 51.81c1.72 1.04 3.41 2.44 4.57 4.12l38.78-17.92c-1.92-3.67-5.78-9.97-11.3-15.15");
}

.kwmegfb7a {
  d: path("M99.94 107.75c3.84-3.11 6.83-6.69 6.83-6.69l-31.6-28.07s-.82 1.19-2.28 2.37c-1.46 1.17-3.52 1.85-3.52 1.85l22.15 36.29s4.59-2.64 8.42-5.75");
}

.kyr-omblw {
  d: path("M49.94 66.3a13.7 13.7 0 0 1-.15-3.18L7.62 72.21c.05.33.08.67.14 1c1.28 7.81 4.1 15 8.1 21.29l37.1-21.51c-1.53-1.86-2.6-4.13-3.02-6.69");
}

.mk30hxbkt {
  d: path("M52.95 72.99L15.85 94.5a57.1 57.1 0 0 0 11.8 13.35L58.1 76.98c-1.99-.91-3.75-2.28-5.15-3.99");
}

.omwu0h0ye {
  stop-color: var(--svg-color--fff9c4, #fff9c4);
  stop-opacity: 0;
}

.pvwmlqbjg {
  d: path("m65.72 78.4l17.96 38.75s7.12-2.36 14.65-8.16c7.33-5.65 11.93-12.42 11.93-12.42L75.3 72.99s-1.3 1.84-3.99 3.51c-2.7 1.68-5.59 1.9-5.59 1.9");
}

.qq4gjn1xo {
  d: path("M62.53 49.83L44.8 10.33s-7.16 2.24-14.78 7.91C22.61 23.76 17.9 30.45 17.9 30.45l34.97 24.62s1.33-1.82 4.05-3.45s5.61-1.79 5.61-1.79");
}

.s5lrcw9lk {
  stop-color: var(--svg-color--80deea, #80deea);
  stop-opacity: 0.5;
}

.s9loqbbut {
  fill: var(--svg-color--212121, #212121);
  d: path("M54.87 9.92C23.88 14.99 2.83 44.3 7.9 75.29s34.38 52.05 65.37 46.97s52.05-34.38 46.97-65.37S85.86 4.84 54.87 9.92m11.5 70.21C58.6 81.4 51.3 76.16 50.03 68.39S54 53.32 61.77 52.05s15.07 3.97 16.34 11.74c1.37 7.75-3.87 15.05-11.74 16.34");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.sau8_ccyd {
  d: path("M76.46 71.57c-.91 1.61-2.23 2.81-2.23 2.81l32.03 27.21s3.56-3.94 6.71-9.43c3.61-6.29 4.87-10.82 4.87-10.82L78.05 67.83s-.48 1.78-1.59 3.74");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.ubcaonr9g {
  d: path("M51.94 56.39c.94-1.59 2.28-2.77 2.28-2.77L21.99 25.51s-3.63 3.88-6.87 9.32c-3.71 6.23-5.05 10.74-5.05 10.74l40.21 14.54s.52-1.78 1.66-3.72");
}

.xjoe-_b7o {
  d: path("M117.16 83.31L78.02 67.03s-.34 1.46-1 3.07s-1.73 2.9-1.73 2.9l34.96 23.58s1.93-2.72 3.93-6.5s2.98-6.77 2.98-6.77");
}

.xwa60cb6r {
  fill: var(--svg-color--6c9eb4, #6c9eb4);
  d: path("M64 41.2c-12.77 0-23.04 10.16-23.04 22.8S51.23 86.8 64 86.8S87.04 76.63 87.04 64S76.77 41.2 64 41.2m0 36.95c-7.97 0-14.4-6.36-14.4-14.25S56.03 49.64 64 49.65s14.4 6.36 14.4 14.25c.09 7.89-6.34 14.25-14.4 14.25");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.xxi_4jb6i {
  fill: var(--svg-color--b9e4ea, #b9e4ea);
  d: path("M54.79 7.76C23.76 12.84 2.67 42.18 7.76 73.21s34.43 52.11 65.46 47.03s52.11-34.43 47.03-65.46C115.16 23.76 85.82 2.67 54.79 7.76m11.51 70.3c-7.78 1.27-15.09-3.98-16.36-11.76s3.98-15.09 11.76-16.36s15.09 3.98 16.36 11.76c1.37 7.76-3.88 15.07-11.76 16.36");
}

.y-k8z6bvj {
  fill: var(--svg-color--616161, #616161);
  d: path("M118.18 124H9.82C6.6 124 4 121.4 4 118.18V9.82C4 6.6 6.6 4 9.82 4h108.37C121.4 4 124 6.6 124 9.82v108.37c0 3.21-2.6 5.81-5.82 5.81");
}

.z1t-t9bjk {
  d: path("m7.35 57.71l42.4 7.51s-.03-1.23.07-2.69c.11-1.46.46-2.42.46-2.42L10.07 45.57s-.92 2.29-1.71 5.83s-1.01 6.31-1.01 6.31");
}

</style>
